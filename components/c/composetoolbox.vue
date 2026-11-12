<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywvh2o5os.css';
import '../../css/h/h8b9m8b5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ywvh2o5os"/><path class="h8b9m8b5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:composetoolbox" /></template>
