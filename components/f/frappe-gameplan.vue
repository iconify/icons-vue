<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so3tt3b9a.css';
import '../../css/y/yk8mxxbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="so3tt3b9a"/><path class="yk8mxxbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frappe-gameplan" /></template>
