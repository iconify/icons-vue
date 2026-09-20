<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocxedjb1h.css';
import '../../css/h/hh28l1bxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocxedjb1h"/><path class="hh28l1bxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:image-search" /></template>
