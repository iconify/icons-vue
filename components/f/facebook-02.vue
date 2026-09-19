<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da9xnqbfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="da9xnqbfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:facebook-02" /></template>
