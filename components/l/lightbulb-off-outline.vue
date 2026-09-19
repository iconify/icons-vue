<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4kwtb3sj.css';
import '../../css/l/lw-tv69tr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4kwtb3sj"/><path clip-rule="evenodd" class="lw-tv69tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:lightbulb-off-outline" /></template>
