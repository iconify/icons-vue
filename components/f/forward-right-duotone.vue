<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbwsmacmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbwsmacmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:forward-right-duotone" /></template>
