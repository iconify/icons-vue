<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-t2gnbbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-t2gnbbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:magic-wand-02" /></template>
