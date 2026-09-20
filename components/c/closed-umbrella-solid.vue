<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi8p0o5-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zi8p0o5-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:closed-umbrella-solid" /></template>
