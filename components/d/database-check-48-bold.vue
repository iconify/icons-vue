<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbbfuqbum.css';
import '../../css/n/n1uvowbjw.css';
import '../../css/o/o_1vsrx4z.css';
import '../../css/y/y9mg2tbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kbbfuqbum"/><path class="n1uvowbjw"/><path class="o_1vsrx4z"/><path class="y9mg2tbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:database-check-48-bold" /></template>
