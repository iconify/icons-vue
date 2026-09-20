<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js71uubxl.css';
import '../../css/g/gwy33kf_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="js71uubxl"/><path class="gwy33kf_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:draft-filled" /></template>
