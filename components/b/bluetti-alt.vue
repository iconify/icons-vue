<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kglf9cg5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kglf9cg5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bluetti-alt" /></template>
