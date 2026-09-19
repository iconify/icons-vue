<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq5ve83fc.css';
import '../../css/o/o4q7kwbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wq5ve83fc"/><path class="o4q7kwbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-mail" /></template>
