<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqccwibwr.css';
import '../../css/b/b09xyt_lu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqccwibwr"/><path class="b09xyt_lu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flame-bold-duotone" /></template>
