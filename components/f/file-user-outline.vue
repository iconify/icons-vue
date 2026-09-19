<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0ogznero.css';
import '../../css/c/cgf21cybt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0ogznero"/><path clip-rule="evenodd" class="cgf21cybt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:file-user-outline" /></template>
