<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apugdvb-c.css';
import '../../css/p/pt1w2bihr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="apugdvb-c"/><path clip-rule="evenodd" class="pt1w2bihr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:image-alt-solid" /></template>
