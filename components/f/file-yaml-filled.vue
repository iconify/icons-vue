<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bul2c6-4f.css';
import '../../css/a/adspdac1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bul2c6-4f"/><path class="adspdac1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-yaml-filled" /></template>
