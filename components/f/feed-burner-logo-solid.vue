<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otz185thq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="otz185thq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:feed-burner-logo-solid" /></template>
