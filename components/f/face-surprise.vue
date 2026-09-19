<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxx6cgb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mxx6cgb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:face-surprise" /></template>
