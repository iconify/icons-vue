<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xw8fosbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:light-key" /></template>
<style>
.xw8fosbpx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m5.908 4.901l.881-1.542q.84-1.47 2.485-1.07l7.193 1.754q1.099.268 1.539 1.31q.441 1.042-.133 2.017l-2.977 5.06q-.565.962-1.673 1.093q-1.108.132-1.883-.67l-.59-.61v5.417l3.744 3.276q.055.048.101.107q.045.058.077.125q.033.066.052.137t.024.145t-.004.147q-.01.073-.034.143q-.023.07-.06.134t-.086.12q-.098.112-.232.178q-.133.066-.282.076t-.29-.038q-.142-.047-.254-.146L10 18.997l-3.506 3.067q-.112.099-.254.146q-.141.048-.29.038t-.282-.076q-.134-.066-.232-.178q-.049-.056-.086-.12t-.06-.134q-.024-.07-.034-.143q-.009-.073-.004-.147t.024-.145t.052-.137q.032-.067.077-.125q.046-.059.101-.107L9.25 17.66v-6.969L6.243 7.58q-1.172-1.214-.335-2.679");
}

</style>
