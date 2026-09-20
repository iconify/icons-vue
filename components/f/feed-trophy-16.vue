<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2q6z65vi.css';
import '../../css/h/hbv-qyu8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v2q6z65vi"/><path class="hbv-qyu8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:feed-trophy-16" /></template>
