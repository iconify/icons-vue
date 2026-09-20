<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4uh-95df.css';
import '../../css/b/bh93e5uni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4uh-95df"/><path class="bh93e5uni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:download-alt" /></template>
