<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smb428ckv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="smb428ckv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:0" /></template>
