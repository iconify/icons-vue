<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-y0upb3c.css';
import '../../css/h/hmwkp1a3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b-y0upb3c"/><path clip-rule="evenodd" class="hmwkp1a3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:instagram-solid" /></template>
