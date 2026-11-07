<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvude-bvd.css';
import '../../css/r/rgo0fe4hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvude-bvd"/><path class="rgo0fe4hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:armchair-bold-duotone" /></template>
