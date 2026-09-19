<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glmuf-bnw.css';
import '../../css/x/x6l88_bcz.css';
import '../../css/o/oy2wq8uic.css';
import '../../css/z/zujvlmw1b.css';
import '../../css/j/j7bkwkbef.css';
import '../../css/u/us_x7ntss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect transform="rotate(-45 256 256.002)" class="glmuf-bnw"/><rect transform="rotate(45 257.409 254.582)" class="x6l88_bcz"/><circle class="oy2wq8uic"/><circle class="zujvlmw1b"/><circle class="j7bkwkbef"/><circle class="us_x7ntss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:bandage-outline" /></template>
