<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2ykngb7r.css';
import '../../css/b/brphuvboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="w2ykngb7r"/><path class="brphuvboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:compass-alt" /></template>
