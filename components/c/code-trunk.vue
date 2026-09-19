<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh_nvlg2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xh_nvlg2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:code-trunk" /></template>
