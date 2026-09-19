<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6wz8cb3t.css';
import '../../css/o/owu91ypwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="t6wz8cb3t"/><path class="owu91ypwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:eye-off-fill" /></template>
