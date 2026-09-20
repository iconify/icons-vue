<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8bm1jbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:celebration-outline-sharp" /></template>
<style>
.s8bm1jbxr {
  fill: currentColor;
  d: path("m3.596 20.346l3.77-10.538l6.769 6.769zM5.242 18.7l7.05-2.5l-4.55-4.55zm8.174-5.842l-.627-.627l7.082-7.083l2.083 2.083l-.588.627l-1.475-1.475zM10.108 9.55l-.627-.627l1.911-1.911L9.47 5.089l.627-.628l2.55 2.55zm1.654 1.654l-.627-.627l4.475-4.475l-2.475-2.475l.627-.627l3.102 3.102zm3.307 3.308l-.627-.627l2.775-2.775l2.775 2.775l-.627.627l-2.148-2.148zM5.242 18.7");
}

</style>
