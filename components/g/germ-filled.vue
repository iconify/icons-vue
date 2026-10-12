<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg86vcuii.css';
import '../../css/c/c-xbtmutf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lg86vcuii"/><path clip-rule="evenodd" class="c-xbtmutf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:germ-filled" /></template>
