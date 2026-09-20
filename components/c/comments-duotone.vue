<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xer9j-beb.css';
import '../../css/o/otnxsdo2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xer9j-beb"/><path clip-rule="evenodd" class="otnxsdo2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:comments-duotone" /></template>
