<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdfy6e8nd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdfy6e8nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:box" /></template>
