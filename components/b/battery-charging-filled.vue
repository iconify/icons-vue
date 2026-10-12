<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0tzg361r.css';
import '../../css/u/ubprlmtat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0tzg361r"/><path class="ubprlmtat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:battery-charging-filled" /></template>
