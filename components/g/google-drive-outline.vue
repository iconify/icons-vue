<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9pkgxbie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p9pkgxbie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:google-drive-outline" /></template>
