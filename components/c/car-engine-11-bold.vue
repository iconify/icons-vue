<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c89x4jb8t.css';
import '../../css/l/l2c2myl2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c89x4jb8t"/><path class="l2c2myl2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:car-engine-11-bold" /></template>
