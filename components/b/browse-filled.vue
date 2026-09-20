<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhi_7zbfl.css';
import '../../css/m/mjirkcbxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhi_7zbfl"/><path class="mjirkcbxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:browse-filled" /></template>
