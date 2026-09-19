<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/n/n4pernbka.css';
import '../../css/x/x7s0ksbho.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlnImqe7h"><g class="ufeehvblu"><path class="n4pernbka"/><path class="x7s0ksbho"/></g></mask></defs><path mask="url(#SVGlnImqe7h)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:coupon" /></template>
