<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfr5h3cft.css';
import '../../css/b/b4j54ubbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfr5h3cft"/><path class="b4j54ubbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chevrons-left-filled" /></template>
