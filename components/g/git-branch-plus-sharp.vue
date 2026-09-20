<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q07upcb-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q07upcb-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-branch-plus-sharp" /></template>
