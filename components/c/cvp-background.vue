<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="o4axjw8xr"/><path class="c_p1s6bkm"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cvp-background" /></template>
<style>
.c_p1s6bkm {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.402 5.501H9.62l1.6-1.002H9.19zm.555 2.546l1.186-2.099H6.804L5.675 8.127zm-.113.438v2.33h-2.39v-2.33zm4.927.884l1.6.965h2.095l-1.6-.965zm-.018 10.16h2l1.684-.988H14.32zm-3.149-5.774l1.6.97H9.106l-1.6-.97zm6.528-.475v2.33h2.385v-2.33zm-1.309-2.536l1.186 2.103l2.283.08l-1.13-2.184zm-6.87.503l1.186 2.104h-2.34L5.67 11.167zm6.87 6.899l1.186-2.104l2.283-.08l-1.13 2.184zM14.65 4.47h-2.316l1.247 2.123h2.339zm.733.377l1.026 1.864l1.789.927l-.989-1.732l-1.825-1.064zm-2.955 4.094l1.163-2.005l2.376.113l-1.158 1.892h-2.385zm2.777.155l1.237-1.929l1.977 1.115l-1.195 1.967zM4 10.556l1.096-1.704v1.976L4 12.706zm1.332.818l-1.28 2.061l1.233 2.033l1.139-2.033zm.164 4.423l1.271-2.056l2.113 1.196l-1.299 1.962l-2.085-1.097zm2.052 1.469l-1.722-.828l.95 1.713l1.704.964zm1.661 2.226l-1.167-2.07h2.415l1.11 2.07zm1.836-11.134l-.974 1.703l1.882-1.082l.819-1.605l-1.732.984zm-1.11-2.58l1.947-1.213l1.224 2.07l-2.047 1.233l-1.13-2.09zm-.297.363l-1.36 2.057l1.242 1.971l1.19-1.976zm-1.36 2.795v2.057l1.044 1.675v-2.056zm.997 6.146L8.01 16.951h2.471l1.13-1.869zm1.902 1.567l.988-1.647l1.68-.993l-1.069 1.765zm1.656-.48l-1.962 1.148l1.251 2.08l1.916-1.195l-1.2-2.033zm1.864-4.814l1.035 1.713v2.085l-1.035-1.694zm-.255 2.565l1.224 1.934l-1.341 2.052l-1.19-1.986zm4.311-5.355l-1.186 2.023l1.092 2.132L20 10.588zm.08 4.659l1.13-1.822v1.996l-1.13 1.67z");
}

.ft5dv1b6b {
  fill: none;
}

.o4axjw8xr {
  fill: var(--svg-color--7899f8, #7899f8);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
