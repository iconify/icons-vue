<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpf30lb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpf30lb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:input-field" /></template>
