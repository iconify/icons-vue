<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akl-4bbmb.css';
import '../../css/b/b08tyi05f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akl-4bbmb"/><path class="b08tyi05f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-wechat-stroke-filled" /></template>
