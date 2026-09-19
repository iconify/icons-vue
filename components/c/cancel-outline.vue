<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol05o0b3n.css';
import '../../css/b/buewkbcgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ol05o0b3n"/><path clip-rule="evenodd" class="buewkbcgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:cancel-outline" /></template>
