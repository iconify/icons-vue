<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9un138cc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9un138cc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:bolt-solid" /></template>
