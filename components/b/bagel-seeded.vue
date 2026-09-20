<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oikneibpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="oikneibpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bagel-seeded" /></template>
