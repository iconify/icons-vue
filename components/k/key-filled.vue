<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzj9gkb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dzj9gkb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:key-filled" /></template>
