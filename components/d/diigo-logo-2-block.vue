<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/befu3bcgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="befu3bcgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:diigo-logo-2-block" /></template>
