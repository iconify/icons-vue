<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj43gzrlp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mj43gzrlp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:link-unlink" /></template>
