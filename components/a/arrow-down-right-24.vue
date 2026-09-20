<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3b46jbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3b46jbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:arrow-down-right-24" /></template>
