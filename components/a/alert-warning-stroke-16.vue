<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur6ybxbzg.css';
import '../../css/p/p9hlq3xpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ur6ybxbzg"/><circle class="p9hlq3xpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:alert-warning-stroke-16" /></template>
