<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8rxm1btm.css';
import '../../css/j/ji5_h82hg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b8rxm1btm"/><path class="ji5_h82hg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:harddrive-o" /></template>
