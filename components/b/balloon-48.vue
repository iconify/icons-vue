<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b76cn79oc.css';
import '../../css/j/j4audb3xv.css';
import '../../css/f/fvcv6nbrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b76cn79oc"/><path class="j4audb3xv"/><path class="fvcv6nbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:balloon-48" /></template>
