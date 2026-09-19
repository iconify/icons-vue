<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9qtzj42n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9qtzj42n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:connectivity-test" /></template>
