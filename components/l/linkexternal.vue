<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4nnu3b-h.css';
import '../../css/s/s_rjlabju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i4nnu3b-h"/><path class="s_rjlabju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:linkexternal" /></template>
