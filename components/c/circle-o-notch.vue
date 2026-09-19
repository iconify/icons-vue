<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suoc8zbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1728,"height":1728};
const content = `<path class="suoc8zbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:circle-o-notch" /></template>
