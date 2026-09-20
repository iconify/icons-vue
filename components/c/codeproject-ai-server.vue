<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh0rf-b9f.css';
import '../../css/b/b54wsupbd.css';
import '../../css/t/trippqbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kh0rf-b9f"/><path class="b54wsupbd"/><path class="trippqbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:codeproject-ai-server" /></template>
