<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/seopr-2dr.css';
import '../../css/i/iwarbo7oi.css';
import '../../css/p/ptikcmbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="seopr-2dr"/><path class="iwarbo7oi"/><path class="ptikcmbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-pdf-filled" /></template>
