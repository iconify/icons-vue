<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbtvgabzb.css';
import '../../css/i/igsxkccpo.css';
import '../../css/l/lybvyzwhf.css';
import '../../css/v/vseb-gbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rbtvgabzb"/><path class="igsxkccpo"/><path class="lybvyzwhf"/><path class="vseb-gbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:anchor-20" /></template>
