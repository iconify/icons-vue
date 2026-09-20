<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e17qmzbbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:brightness-2-outline-sharp" /></template>
<style>
.e17qmzbbb {
  fill: currentColor;
  d: path("M9.5 20q3.325 0 5.663-2.337T17.5 12t-2.337-5.663T9.5 4h-.525q-.25 0-.475.05q1.425 1.65 2.213 3.688T11.5 12t-.788 4.263T8.5 19.95q.225.05.475.05zm0 2q-1.325 0-2.588-.337T4.5 20.65Q6.825 19.3 8.163 17T9.5 12T8.162 7T4.5 3.35q1.15-.675 2.413-1.012T9.5 2q2.075 0 3.9.788t3.175 2.137T18.713 8.1T19.5 12t-.788 3.9t-2.137 3.175t-3.175 2.138T9.5 22m2-10");
}

</style>
