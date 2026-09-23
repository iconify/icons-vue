<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kps4-xb-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kps4-xb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:git-pull-request-unlisted" /></template>
