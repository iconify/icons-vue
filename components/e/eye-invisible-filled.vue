<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqys2lycf.css';
import '../../css/u/u_u3qq80h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pqys2lycf"/><path class="u_u3qq80h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:eye-invisible-filled" /></template>
