<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-wke7znd.css';
import '../../css/p/p1xhgbied.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-wke7znd"/><path clip-rule="evenodd" class="p1xhgbied"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:banknote-check-filled" /></template>
