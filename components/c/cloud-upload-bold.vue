<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jik0uqbax.css';
import '../../css/r/rshns2aav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jik0uqbax"/><path clip-rule="evenodd" class="rshns2aav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-upload-bold" /></template>
