<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oni6cscln.css';
import '../../css/g/gcy3r1rbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oni6cscln"/><path class="gcy3r1rbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hospital-filled" /></template>
