<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng8kr6bhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ng8kr6bhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:happy-person-raising-one-hand" /></template>
