<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8epyabtk.css';
import '../../css/v/v696jcbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8epyabtk"/><path clip-rule="evenodd" class="v696jcbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clipboard-bold" /></template>
