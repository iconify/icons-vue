<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zntd2nx3b.css';
import '../../css/n/n8ql_ybqa.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="clr-i-solid clr-i-solid-path-1 zntd2nx3b"/><path class="clr-i-solid clr-i-solid-path-2 n8ql_ybqa"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:accessibility-2-solid" /></template>
