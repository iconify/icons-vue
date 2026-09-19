<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxofds--v.css';
import '../../css/s/s310mjyrf.css';
import '../../css/g/ghnp_db6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vxofds--v"/><path class="s310mjyrf"/><path class="ghnp_db6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:folder-add-twotone" /></template>
