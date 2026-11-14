<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjchw2bux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjchw2bux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-mic" /></template>
