<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rko7y9uyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rko7y9uyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-eleven-small" /></template>
