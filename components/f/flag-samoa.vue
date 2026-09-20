<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="qkw59p6en"/><path class="upkwynb3e"/><path class="t4rnt6b9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-samoa" /></template>
<style>
.qkw59p6en {
  fill: var(--svg-color--ce1126, #ce1126);
  d: path("M32 5H19v13H0v9a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

.t4rnt6b9d {
  fill: var(--svg-color--fff, #fff);
  d: path("m8.524 8.289l.893-.648l.892.648l-.341-1.049l.893-.649H9.758l-.341-1.049l-.341 1.049H7.972l.893.649zM5.785 9.841l-.341-1.049l-.341 1.049H4l.893.649l-.341 1.049l.892-.648l.893.648l-.341-1.049l.893-.649zm8.014-.607l-.32-.984l-.32.984h-1.034l.837.608l-.32.984l.837-.608l.837.608l-.32-.984l.837-.608zm-2.183 3.01l-.213-.656l-.213.656h-.69l.558.406l-.213.656l.558-.406l.558.406l-.213-.656l.558-.406zm-1.773 3.092l-.426-1.312l-.427 1.312H7.611l1.116.81l-.426 1.312l1.116-.81l1.116.81l-.427-1.312l1.116-.81z");
}

.upkwynb3e {
  fill: var(--svg-color--002b7f, #002b7f);
  d: path("M19 5H4a4 4 0 0 0-4 4v9h19zM9.076 6.591l.341-1.049l.341 1.049h1.103l-.893.649l.341 1.049l-.892-.648l-.893.648l.341-1.049l-.893-.649zm-2.739 4.948l-.893-.649l-.893.649l.341-1.049L4 9.841h1.103l.341-1.049l.341 1.049h1.103l-.892.649zm4.196 5.919l-1.116-.811l-1.116.811l.426-1.312l-1.116-.811H8.99l.426-1.312l.426 1.312h1.379l-1.116.811zm1.428-4.152l-.558-.406l-.558.405l.213-.656l-.558-.405h.69l.213-.656l.213.656h.69l-.558.405zm2.355-2.48l-.837-.608l-.837.608l.32-.984l-.837-.608h1.034l.32-.984l.32.984h1.034l-.837.608z");
}

</style>
