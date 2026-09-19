<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gro_6ubgm.css';
import '../../css/b/b59azjj9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gro_6ubgm"/><path class="b59azjj9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-duplicate-16-solid" /></template>
