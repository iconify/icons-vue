<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3-vhnb6i.css';
import '../../css/j/jik0uqbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j3-vhnb6i"/><path class="jik0uqbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clound-cross-bold" /></template>
