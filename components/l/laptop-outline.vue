<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1_uyh1sv.css';
import '../../css/g/g2kbevgvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s1_uyh1sv"/><path class="g2kbevgvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:laptop-outline" /></template>
