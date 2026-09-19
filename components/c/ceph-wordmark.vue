<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbc6z0ers.css';
import '../../css/s/s5gh9gbtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zbc6z0ers"/><path class="s5gh9gbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:ceph-wordmark" /></template>
