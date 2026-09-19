<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/riyh8pbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":505,"height":512};
const content = `<path class="riyh8pbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:circleci" /></template>
