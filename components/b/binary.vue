<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnytfib0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":768};
const content = `<path class="gnytfib0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:binary" /></template>
