<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fiugobc0l.css';
import '../../css/b/bc69m5bpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fiugobc0l"/><path class="bc69m5bpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:blur" /></template>
