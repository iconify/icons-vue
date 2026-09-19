<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb3enpccq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="nb3enpccq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:clear" /></template>
