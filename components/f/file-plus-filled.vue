<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qos0h86tn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qos0h86tn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:file-plus-filled" /></template>
