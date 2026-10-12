<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpzeqkffn.css';
import '../../css/s/s7rh6qv0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gpzeqkffn"/><path class="s7rh6qv0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-search-filled" /></template>
