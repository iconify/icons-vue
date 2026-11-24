<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f09f9qk1r.css';
import '../../css/t/tegin3b-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f09f9qk1r"/><path class="tegin3b-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:ear-off-filled" /></template>
