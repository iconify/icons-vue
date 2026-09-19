<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyy3z6b2h.css';
import '../../css/b/b0bieq5rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jyy3z6b2h"/><path class="b0bieq5rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:easel-sharp" /></template>
