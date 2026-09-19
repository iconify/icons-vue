<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9-n_p_wf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j9-n_p_wf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:battery-quarter-solid" /></template>
