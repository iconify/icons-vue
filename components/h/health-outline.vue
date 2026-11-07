<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6vco797o.css';
import '../../css/l/lkfeoqf6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6vco797o"/><path clip-rule="evenodd" class="lkfeoqf6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:health-outline" /></template>
