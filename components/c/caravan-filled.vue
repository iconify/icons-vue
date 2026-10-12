<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpcj9efqn.css';
import '../../css/s/s9lr0vb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qpcj9efqn"/><path class="s9lr0vb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:caravan-filled" /></template>
