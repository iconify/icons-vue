<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj8wdoo8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj8wdoo8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:comment-02" /></template>
