<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au450cbud.css';
import '../../css/b/bztrvmj6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<ellipse class="au450cbud"/><circle class="bztrvmj6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:decimal-fill-16" /></template>
