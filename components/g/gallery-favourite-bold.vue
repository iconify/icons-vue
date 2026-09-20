<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9qd5__9z.css';
import '../../css/p/p93a1fbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r9qd5__9z"/><path class="p93a1fbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gallery-favourite-bold" /></template>
