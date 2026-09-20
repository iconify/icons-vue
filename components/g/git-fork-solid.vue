<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec2m1t97f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ec2m1t97f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:git-fork-solid" /></template>
