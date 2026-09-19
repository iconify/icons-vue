<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w88ri53dc.css';
import '../../css/i/i0h_6ybcs.css';
import '../../css/e/etn0ud2ez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w88ri53dc"/><path class="i0h_6ybcs"/><path class="etn0ud2ez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:file-gif-outlined" /></template>
