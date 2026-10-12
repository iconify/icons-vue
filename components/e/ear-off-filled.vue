<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7sy6m7uh.css';
import '../../css/t/tegin3b-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c7sy6m7uh"/><path class="tegin3b-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:ear-off-filled" /></template>
