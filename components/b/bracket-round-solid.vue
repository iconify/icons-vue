<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxlum6bpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxlum6bpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:bracket-round-solid" /></template>
