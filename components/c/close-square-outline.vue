<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc5t7t3ch.css';
import '../../css/g/g4e643m4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rc5t7t3ch"/><path clip-rule="evenodd" class="g4e643m4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:close-square-outline" /></template>
