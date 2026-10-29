<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gi7onfq8a.css';
import '../../css/a/azkasfb2o.css';
import '../../css/g/gzejcj1pe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gi7onfq8a wm-shadow"/><path class="azkasfb2o wm-k"/><path class="gzejcj1pe wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:align-center" /></template>
