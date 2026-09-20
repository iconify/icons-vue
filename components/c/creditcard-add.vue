<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hoee0wbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hoee0wbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:creditcard-add" /></template>
