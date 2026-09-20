<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_w-hxjse.css';
import '../../css/z/zbx9303xv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_w-hxjse"/><path class="zbx9303xv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:bug-solid" /></template>
