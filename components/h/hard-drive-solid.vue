<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcnyyb28t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcnyyb28t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:hard-drive-solid" /></template>
