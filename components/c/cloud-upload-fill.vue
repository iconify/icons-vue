<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_z7jbbuz.css';
import '../../css/g/gxjodwbrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_z7jbbuz"/><path class="gxjodwbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:cloud-upload-fill" /></template>
