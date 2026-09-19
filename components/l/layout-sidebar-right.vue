<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm29z5bmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hm29z5bmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:layout-sidebar-right" /></template>
