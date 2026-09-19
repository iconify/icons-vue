<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od1rprkuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="od1rprkuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bluray" /></template>
