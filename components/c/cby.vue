<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3jvjrbaz.css';
import '../../css/d/d9k27_-5v.css';
import '../../css/n/n1h2j9b4e.css';
import '../../css/x/x-d4y8bfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3jvjrbaz"/><path class="d9k27_-5v"/><path class="n1h2j9b4e"/><path class="x-d4y8bfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cby" /></template>
