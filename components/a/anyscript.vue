<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3dnpkz9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b3dnpkz9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:anyscript" /></template>
