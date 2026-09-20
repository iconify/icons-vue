<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c22dl68fr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:apk-document-outline" /></template>
<style>
.c22dl68fr {
  fill: currentColor;
  d: path("M7.962 18.23h8.076q-.08-.993-.596-1.816q-.515-.824-1.373-1.308l.758-1.373q.05-.081.015-.177q-.034-.096-.12-.146q-.082-.05-.165-.026t-.134.106l-.783 1.404q-.384-.161-.798-.245q-.413-.083-.842-.083t-.833.083t-.808.245l-.782-1.404q-.05-.086-.143-.106q-.094-.019-.18.031q-.02 0-.081.318l.777 1.373q-.858.485-1.383 1.308t-.605 1.817m1.948-1.333q-.121-.121-.121-.283t.12-.282t.283-.121t.274.12t.111.284t-.111.282t-.274.121t-.282-.121m3.634 0q-.121-.121-.121-.283t.121-.282t.283-.121t.283.12q.12.122.12.284t-.12.282q-.121.121-.283.121t-.283-.121M6.616 21q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3H14.5L19 7.5v11.885q0 .69-.462 1.153T17.384 21zM14 8V4H6.616q-.231 0-.424.192T6 4.615v14.77q0 .23.192.423t.423.192h10.77q.23 0 .423-.192t.192-.424V8zM6 4v4zv16z");
}

</style>
