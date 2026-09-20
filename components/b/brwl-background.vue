<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVGfCrmGeEK)" class="cz7rg2b_o"/><path fill="url(#SVGaX2UKbFK)" clip-rule="evenodd" class="iq7f0ydpy"/><path class="ais0mzb3b"/><path class="wwxvsnbfj"/></g><defs><linearGradient id="SVGfCrmGeEK" x1="12" x2="12" y1="5.558" y2="20" gradientUnits="userSpaceOnUse"><stop class="apreibcac"/><stop offset=".52" class="jsomi4bkm"/><stop offset="1" class="skxaxac-k"/></linearGradient><linearGradient id="SVGaX2UKbFK" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="ww0ri-htm"/><stop offset="1" class="zhmzdcc8f"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:brwl-background" /></template>
<style>
.ais0mzb3b {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.207 7.764c.137 0 .203.174.108.273l-3.049 3.214c-.094.104-.028.273.108.273h1.106c.099 0 .174.099.146.203l-.781 2.978a.155.155 0 0 1-.146.118H6.937c-.066 0-.113-.056-.113-.122v-.029l.437-1.736a.11.11 0 0 1 .109-.09h.517c.07 0 .132-.047.146-.117l.64-2.645c.028-.103-.047-.202-.146-.202h-.296a.12.12 0 0 1-.113-.108l.005-.043l.48-1.877a.11.11 0 0 1 .108-.09z");
}

.apreibcac {
  stop-color: var(--svg-color--dd4076, #dd4076);
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.cz7rg2b_o {
  d: path("M20 12a8 8 0 1 1-16 0a8 8 0 0 1 16 0");
}

.ft5dv1b6b {
  fill: none;
}

.iq7f0ydpy {
  fill-rule: evenodd;
  d: path("M12 19.53a7.53 7.53 0 1 0 0-15.06a7.53 7.53 0 0 0 0 15.058m0 .47a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

.jsomi4bkm {
  stop-color: var(--svg-color--af3466, #af3466);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.skxaxac-k {
  stop-color: var(--svg-color--471840, #471840);
}

.ww0ri-htm {
  stop-color: var(--svg-color--f42776, #f42776);
}

.wwxvsnbfj {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.27 11.058c.137 0 .203.175.109.273l-3.059 3.22a.16.16 0 0 0-.047.107c0 .085.061.165.155.165h2.918a.13.13 0 0 0 .103-.047l1.205-1.19a.4.4 0 0 0 .104-.18l.306-1.105c.056-.189.291-.236.4-.076l.094.127a.33.33 0 0 1 .047.283l-.31 1.21a.4.4 0 0 1-.11.183l-1.25 1.195a.22.22 0 0 1-.156.066h-6a.23.23 0 0 0-.203.122a.214.214 0 0 0 .033.26l.372.517a.16.16 0 0 0 .104.042h6.588c.042 0 .08-.019.108-.047l1.214-1.318a.4.4 0 0 0 .094-.174l.353-1.346a.16.16 0 0 0-.037-.155l-.48-.485a.17.17 0 0 1-.043-.113q-.002-.063.048-.113l.94-.974a.4.4 0 0 0 .1-.178l.197-.753a.25.25 0 0 0-.056-.236l-.377-.4a.304.304 0 0 0-.518.165l-.056.32a.33.33 0 0 1-.085.16l-.96.941a.14.14 0 0 1-.11.05a.14.14 0 0 1-.11-.05l-.246-.282a.164.164 0 0 1 .005-.226l.918-.861a.4.4 0 0 0 .103-.188l.193-.767a.25.25 0 0 0-.056-.231l-1.116-1.177a.1.1 0 0 0-.08-.032h-1.703a.146.146 0 0 0-.146.117l-.748 2.974c-.024.104.047.203.146.203h1.106z");
}

.zhmzdcc8f {
  stop-color: var(--svg-color--e92776, #e92776);
}

</style>
